<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntjuo63ty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ntjuo63ty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-down-right" {...props}></Icon>
