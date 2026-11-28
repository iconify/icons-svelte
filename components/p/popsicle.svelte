<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ia7a3j7zv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ia7a3j7zv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:popsicle" {...props}></Icon>
