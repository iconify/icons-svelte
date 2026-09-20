<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlumm6bif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mlumm6bif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:css3-fill" {...props}></Icon>
