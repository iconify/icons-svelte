<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iydi5xvdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="iydi5xvdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:heading-20" {...props}></Icon>
