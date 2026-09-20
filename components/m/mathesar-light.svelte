<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sf73475fd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sf73475fd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mathesar-light" {...props}></Icon>
