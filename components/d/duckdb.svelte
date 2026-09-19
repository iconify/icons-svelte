<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkkcrdbzx.css';
import '../../css/z/zkseeuhgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="dkkcrdbzx"/><path class="st0 zkseeuhgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:duckdb" {...props}></Icon>
