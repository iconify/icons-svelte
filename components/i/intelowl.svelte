<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uonhm3b8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uonhm3b8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:intelowl" {...props}></Icon>
