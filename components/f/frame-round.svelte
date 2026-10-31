<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvdw0obcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uvdw0obcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:frame-round" {...props}></Icon>
