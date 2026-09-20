<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6ny-pb4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="u6ny-pb4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:add" {...props}></Icon>
