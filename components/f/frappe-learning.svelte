<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ce1v0cccs.css';
import '../../css/x/xnqtkuy1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ce1v0cccs"/><path class="xnqtkuy1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:frappe-learning" {...props}></Icon>
