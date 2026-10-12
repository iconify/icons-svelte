<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jd_z49b8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jd_z49b8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:chain-broken-20" {...props}></Icon>
