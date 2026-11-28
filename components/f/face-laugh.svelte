<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scqzr4rjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="scqzr4rjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:face-laugh" {...props}></Icon>
