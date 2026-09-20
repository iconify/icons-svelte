<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jl7biob5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jl7biob5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:egg" {...props}></Icon>
