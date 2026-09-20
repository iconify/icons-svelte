<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oesco-xxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oesco-xxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pushover-light" {...props}></Icon>
