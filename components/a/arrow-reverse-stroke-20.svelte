<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_k7z_b-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n_k7z_b-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:arrow-reverse-stroke-20" {...props}></Icon>
