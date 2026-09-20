<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wryaqu8dm.css';
import '../../css/v/vbv8sqv-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wryaqu8dm"/><path class="vbv8sqv-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:logo-soundcloud-1" {...props}></Icon>
