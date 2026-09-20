<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfwm6qbkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tfwm6qbkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:aya-cohere" {...props}></Icon>
