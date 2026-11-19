<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oogezyb0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oogezyb0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:excaliself-dark" {...props}></Icon>
