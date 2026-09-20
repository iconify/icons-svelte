<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iu7segb_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iu7segb_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:image-minus" {...props}></Icon>
