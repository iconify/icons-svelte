<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7qy0ubco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="f7qy0ubco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:line-double" {...props}></Icon>
