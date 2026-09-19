<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u60ek76zo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u60ek76zo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cloud-rain-wind-alt-filled" {...props}></Icon>
