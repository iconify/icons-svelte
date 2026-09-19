<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qb-8z_bop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qb-8z_bop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:droplet-fill" {...props}></Icon>
