<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1uwjw_ky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e1uwjw_ky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-planetscale" {...props}></Icon>
