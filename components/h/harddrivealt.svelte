<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ycdoa4ifx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ycdoa4ifx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:harddrivealt" {...props}></Icon>
