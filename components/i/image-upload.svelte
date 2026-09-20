<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/si5p7gb_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="si5p7gb_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:image-upload" {...props}></Icon>
