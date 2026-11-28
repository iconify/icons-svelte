<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n07l6ebha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n07l6ebha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:ice-cream" {...props}></Icon>
