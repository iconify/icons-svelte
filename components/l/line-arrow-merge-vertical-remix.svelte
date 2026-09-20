<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xk4uyrk5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xk4uyrk5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:line-arrow-merge-vertical-remix" {...props}></Icon>
