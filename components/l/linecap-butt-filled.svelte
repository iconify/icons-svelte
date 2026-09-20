<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myx9f4b_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="myx9f4b_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:linecap-butt-filled" {...props}></Icon>
