<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ap5--l7rc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ap5--l7rc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:linkding-light" {...props}></Icon>
