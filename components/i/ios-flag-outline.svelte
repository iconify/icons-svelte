<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d35w0wbdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d35w0wbdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-flag-outline" {...props}></Icon>
