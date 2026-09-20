<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbn1uy2ld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kbn1uy2ld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:nav-get-started" {...props}></Icon>
