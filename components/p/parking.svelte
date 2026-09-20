<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sggwcl_gf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sggwcl_gf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:parking" {...props}></Icon>
