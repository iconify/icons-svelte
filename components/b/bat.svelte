<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3zwbtxdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1025};
const content = `<path class="p3zwbtxdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:bat" {...props}></Icon>
