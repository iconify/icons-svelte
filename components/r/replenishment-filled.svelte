<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3c_gcb-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="f3c_gcb-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:replenishment-filled" {...props}></Icon>
