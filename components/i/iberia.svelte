<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/alx9w2vyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="alx9w2vyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:iberia" {...props}></Icon>
