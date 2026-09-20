<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jic3_cbyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jic3_cbyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:duckdb" {...props}></Icon>
