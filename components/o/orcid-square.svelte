<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rq1zmjr3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="rq1zmjr3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:orcid-square" {...props}></Icon>
