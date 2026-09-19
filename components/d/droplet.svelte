<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kx4405b0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kx4405b0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:droplet" {...props}></Icon>
