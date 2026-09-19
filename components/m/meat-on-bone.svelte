<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gowaesbpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gowaesbpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:meat-on-bone" {...props}></Icon>
