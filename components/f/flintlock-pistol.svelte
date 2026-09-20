<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_d9kjclj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="i_d9kjclj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:flintlock-pistol" {...props}></Icon>
