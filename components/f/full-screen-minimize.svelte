<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvxbm69xm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nvxbm69xm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:full-screen-minimize" {...props}></Icon>
