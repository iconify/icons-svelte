<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmp4o6v6i.css';
import '../../css/w/wlilhubec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bmp4o6v6i"/><path class="wlilhubec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:building-real-eastate-house-1" {...props}></Icon>
