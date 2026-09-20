<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dn1l0mbid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dn1l0mbid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:infuse-two-outline" {...props}></Icon>
