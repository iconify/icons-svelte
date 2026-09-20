<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jl3zgt9lr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jl3zgt9lr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-right3-filled" {...props}></Icon>
