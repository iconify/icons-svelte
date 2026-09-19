<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kx3ploiaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kx3ploiaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:addthis" {...props}></Icon>
