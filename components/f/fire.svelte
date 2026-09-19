<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wyj6__bvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wyj6__bvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:fire" {...props}></Icon>
