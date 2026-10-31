<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k94-9lb7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k94-9lb7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:owl-head-round" {...props}></Icon>
