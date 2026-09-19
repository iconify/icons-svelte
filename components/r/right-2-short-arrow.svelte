<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1n2l3blm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h1n2l3blm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:right-2-short-arrow" {...props}></Icon>
