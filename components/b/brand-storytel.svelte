<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1l3bd9xt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y1l3bd9xt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-storytel" {...props}></Icon>
