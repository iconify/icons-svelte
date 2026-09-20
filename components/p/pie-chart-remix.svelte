<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tokqv9rxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tokqv9rxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:pie-chart-remix" {...props}></Icon>
