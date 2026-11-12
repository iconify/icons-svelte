<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfh9e8-4g.css';
import '../../css/a/aou0j_yla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qfh9e8-4g"/><path class="aou0j_yla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:notepad-plus-plus-dark" {...props}></Icon>
