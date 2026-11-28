<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_exy2bih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_exy2bih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:bookmark-minus-solid" {...props}></Icon>
