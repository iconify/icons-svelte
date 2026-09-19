<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9mmqfbbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m9mmqfbbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:plant-pot-filled" {...props}></Icon>
