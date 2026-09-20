<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qz_yzzudd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qz_yzzudd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:analog-watch" {...props}></Icon>
