<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ux334-gix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ux334-gix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:broccoli" {...props}></Icon>
