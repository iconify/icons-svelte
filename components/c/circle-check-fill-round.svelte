<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uizmpkbom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uizmpkbom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-check-fill-round" {...props}></Icon>
