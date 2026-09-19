<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q39_z9bzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path clip-rule="evenodd" class="q39_z9bzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:check-mark" {...props}></Icon>
