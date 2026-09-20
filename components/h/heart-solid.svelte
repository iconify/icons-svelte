<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/no_ee8bpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="no_ee8bpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:heart-solid" {...props}></Icon>
