<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zp8doyjes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zp8doyjes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:bag" {...props}></Icon>
