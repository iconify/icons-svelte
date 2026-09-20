<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a64e_yb6y.css';
import '../../css/u/uygqtsbxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="a64e_yb6y"/><path class="uygqtsbxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:double-curly-loop" {...props}></Icon>
