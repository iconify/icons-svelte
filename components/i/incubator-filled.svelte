<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv_7cr1qr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gv_7cr1qr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:incubator-filled" {...props}></Icon>
