<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cov2xcb9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cov2xcb9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:link-x" {...props}></Icon>
