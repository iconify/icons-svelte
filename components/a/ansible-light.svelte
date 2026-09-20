<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cft0r1bwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cft0r1bwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ansible-light" {...props}></Icon>
