<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksjvsb74q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ksjvsb74q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:duckdb" {...props}></Icon>
