<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jog8yfyqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":3,"height":16};
const content = `<path class="jog8yfyqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:kebab-vertical" {...props}></Icon>
