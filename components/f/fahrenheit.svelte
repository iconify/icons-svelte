<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/as1fvkbzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="as1fvkbzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:fahrenheit" {...props}></Icon>
