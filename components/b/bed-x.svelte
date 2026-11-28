<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dx3cj6qoe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dx3cj6qoe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:bed-x" {...props}></Icon>
