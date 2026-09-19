<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0ic71k9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="s0ic71k9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:bacon" {...props}></Icon>
