<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vi8_w4sav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vi8_w4sav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:reblog" {...props}></Icon>
