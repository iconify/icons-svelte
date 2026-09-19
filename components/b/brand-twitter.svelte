<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_9ma5gfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n_9ma5gfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:brand-twitter" {...props}></Icon>
