<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_--r1bwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="d_--r1bwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:rightmost" {...props}></Icon>
