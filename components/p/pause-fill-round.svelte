<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-zd_5xuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d-zd_5xuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:pause-fill-round" {...props}></Icon>
