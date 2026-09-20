<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsycj_bmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lsycj_bmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:marketplace" {...props}></Icon>
