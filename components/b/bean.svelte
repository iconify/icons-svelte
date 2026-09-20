<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqjnh8bqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="cqjnh8bqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:bean" {...props}></Icon>
