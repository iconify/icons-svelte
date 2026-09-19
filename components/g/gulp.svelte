<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dtfr4tbxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":24};
const content = `<path class="dtfr4tbxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:gulp" {...props}></Icon>
