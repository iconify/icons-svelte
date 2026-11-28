<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cov3g02at.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cov3g02at"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:chevron-circle-right" {...props}></Icon>
