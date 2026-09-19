<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgs_9lbql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="pgs_9lbql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:graph-circle" {...props}></Icon>
