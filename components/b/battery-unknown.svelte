<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vawghnbbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":216,"height":432};
const content = `<path class="vawghnbbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:battery-unknown" {...props}></Icon>
