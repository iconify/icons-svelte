<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aij8cd1pi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="aij8cd1pi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:rfid" {...props}></Icon>
