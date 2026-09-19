<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gcpkd6bjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gcpkd6bjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:podium" {...props}></Icon>
