<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggi05pupf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":668};
const content = `<path class="ggi05pupf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:crown" {...props}></Icon>
