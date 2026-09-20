<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ighpm6bgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ighpm6bgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:medical" {...props}></Icon>
