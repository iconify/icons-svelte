<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz7ctgbrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nz7ctgbrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:bread" {...props}></Icon>
