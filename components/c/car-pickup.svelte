<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehln14cwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ehln14cwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:car-pickup" {...props}></Icon>
