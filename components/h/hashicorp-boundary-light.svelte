<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2n94b11u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c2n94b11u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hashicorp-boundary-light" {...props}></Icon>
