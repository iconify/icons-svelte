<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xlgd_zbki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xlgd_zbki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:headphones-solid" {...props}></Icon>
