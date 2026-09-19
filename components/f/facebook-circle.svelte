<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgb26qb4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pgb26qb4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:facebook-circle" {...props}></Icon>
