<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awoo6h4xx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="awoo6h4xx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:circle-letter-k" {...props}></Icon>
