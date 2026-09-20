<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jm1876bao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jm1876bao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:double-arrow-up-filled" {...props}></Icon>
