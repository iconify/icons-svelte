<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkwr2fbrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wkwr2fbrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:heart" {...props}></Icon>
