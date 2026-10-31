<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uj6fz_blj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uj6fz_blj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:octagon-minus-fill-round" {...props}></Icon>
