<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3n38s0_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n3n38s0_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-left-to-line-fill-round" {...props}></Icon>
