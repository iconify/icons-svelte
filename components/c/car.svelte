<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1y_2yb4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":661};
const content = `<path class="q1y_2yb4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:car" {...props}></Icon>
