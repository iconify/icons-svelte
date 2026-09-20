<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulj6f9bpb.css';
import '../../css/k/k12cdmnwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ulj6f9bpb"/><path class="k12cdmnwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:pyth" {...props}></Icon>
