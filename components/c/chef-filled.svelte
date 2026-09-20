<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/foptdfb_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="foptdfb_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:chef-filled" {...props}></Icon>
