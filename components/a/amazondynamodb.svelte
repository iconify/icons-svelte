<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxy2_nt0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dxy2_nt0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:amazondynamodb" {...props}></Icon>
