<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k36puzb3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k36puzb3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:mail-icon-2" {...props}></Icon>
