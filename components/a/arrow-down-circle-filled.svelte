<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o76u42bxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o76u42bxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-down-circle-filled" {...props}></Icon>
