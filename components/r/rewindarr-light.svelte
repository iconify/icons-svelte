<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgwuwtb6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qgwuwtb6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rewindarr-light" {...props}></Icon>
