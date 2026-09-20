<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfx_deblx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-5,"top":-2};
const content = `<path class="gfx_deblx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:flask" {...props}></Icon>
