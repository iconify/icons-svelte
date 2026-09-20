<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5axs6bmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y5axs6bmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:link-box-variant" {...props}></Icon>
