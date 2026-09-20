<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfnphxbws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zfnphxbws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-alert-circle-2" {...props}></Icon>
