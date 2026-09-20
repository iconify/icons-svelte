<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k56bsdz-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="k56bsdz-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:pin" {...props}></Icon>
