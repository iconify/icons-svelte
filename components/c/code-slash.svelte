<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sm61msbzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sm61msbzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:code-slash" {...props}></Icon>
