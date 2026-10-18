<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3a2h2b9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d3a2h2b9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:lightbulb" {...props}></Icon>
