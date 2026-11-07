<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_vkrn_jr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_vkrn_jr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cloud-linear" {...props}></Icon>
