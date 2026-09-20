<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wg25lbbmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wg25lbbmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-unsplash" {...props}></Icon>
