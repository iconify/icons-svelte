<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjlu5-buy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yjlu5-buy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:filter-bulk-round" {...props}></Icon>
