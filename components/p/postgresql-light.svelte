<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxf7_gb9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sxf7_gb9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:postgresql-light" {...props}></Icon>
