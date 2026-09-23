<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_tz7sbvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o_tz7sbvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:aiometadata-dark" {...props}></Icon>
