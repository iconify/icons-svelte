<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ua3k2blde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ua3k2blde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:requestly-dark" {...props}></Icon>
