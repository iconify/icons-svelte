<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqooozbdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="eqooozbdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:content-clip" {...props}></Icon>
