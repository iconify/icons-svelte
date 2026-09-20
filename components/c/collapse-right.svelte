<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybrcn-9lv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ybrcn-9lv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:collapse-right" {...props}></Icon>
