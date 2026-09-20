<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwgm37udc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uwgm37udc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:bring-forward" {...props}></Icon>
