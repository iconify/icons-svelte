<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owp42ei7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="owp42ei7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:navigation-left" {...props}></Icon>
