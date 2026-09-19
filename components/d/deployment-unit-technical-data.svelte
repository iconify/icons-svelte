<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lc4wb_bqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lc4wb_bqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:deployment-unit-technical-data" {...props}></Icon>
