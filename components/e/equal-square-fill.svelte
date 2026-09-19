<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gv0asac4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="gv0asac4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:equal-square-fill" {...props}></Icon>
