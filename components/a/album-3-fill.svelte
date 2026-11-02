<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s01ctnr_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s01ctnr_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:album-3-fill" {...props}></Icon>
