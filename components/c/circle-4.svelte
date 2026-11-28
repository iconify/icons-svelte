<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pt-jahboz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pt-jahboz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:circle-4" {...props}></Icon>
