<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzz206blm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rzz206blm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:jsreport-light" {...props}></Icon>
