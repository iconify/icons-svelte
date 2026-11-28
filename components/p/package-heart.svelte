<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-zal0bpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p-zal0bpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:package-heart" {...props}></Icon>
