<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5_sp-b6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="j5_sp-b6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:balance-scale" {...props}></Icon>
