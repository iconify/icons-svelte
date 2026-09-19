<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgxzlab4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kgxzlab4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:creative-commons" {...props}></Icon>
