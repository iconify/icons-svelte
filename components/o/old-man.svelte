<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npdwm_bbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path clip-rule="evenodd" class="npdwm_bbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:old-man" {...props}></Icon>
