<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ux6_y-bdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ux6_y-bdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-down" {...props}></Icon>
