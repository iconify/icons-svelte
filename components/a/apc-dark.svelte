<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oil6zn__w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oil6zn__w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:apc-dark" {...props}></Icon>
