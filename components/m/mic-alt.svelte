<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3o-d3q7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-3,"top":-2};
const content = `<path class="f3o-d3q7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:mic-alt" {...props}></Icon>
