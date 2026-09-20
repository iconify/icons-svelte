<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zk-a69bgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="zk-a69bgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:dry" {...props}></Icon>
