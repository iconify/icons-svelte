<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzi7nyb0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uzi7nyb0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ironmount-light" {...props}></Icon>
