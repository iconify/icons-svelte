<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qq-d3dbfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qq-d3dbfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:database-gear" {...props}></Icon>
