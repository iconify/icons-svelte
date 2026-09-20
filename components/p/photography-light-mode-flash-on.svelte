<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qg_55xbyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qg_55xbyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:photography-light-mode-flash-on" {...props}></Icon>
