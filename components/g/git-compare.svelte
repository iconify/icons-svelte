<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_u_6i4jv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c_u_6i4jv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:git-compare" {...props}></Icon>
