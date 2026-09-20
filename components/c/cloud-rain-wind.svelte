<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4eo1f_dz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o4eo1f_dz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:cloud-rain-wind" {...props}></Icon>
