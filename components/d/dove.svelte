<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvcs251if.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gvcs251if"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:dove" {...props}></Icon>
