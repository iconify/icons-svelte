<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eti5oubiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="eti5oubiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:decimal-filled" {...props}></Icon>
