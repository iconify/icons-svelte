<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvj-cvb5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":768};
const content = `<path class="xvj-cvb5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:businesscard" {...props}></Icon>
