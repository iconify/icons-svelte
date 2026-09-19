<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4-6_2nty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n4-6_2nty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-to-top" {...props}></Icon>
