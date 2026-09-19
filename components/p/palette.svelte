<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lb4yqob1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":769,"height":690};
const content = `<path class="lb4yqob1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:palette" {...props}></Icon>
