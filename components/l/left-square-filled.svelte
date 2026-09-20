<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfhiwccbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="hfhiwccbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:left-square-filled" {...props}></Icon>
