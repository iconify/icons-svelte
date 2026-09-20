<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k20xl2bcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="k20xl2bcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:low-vision" {...props}></Icon>
