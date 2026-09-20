<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w44_k6bry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="w44_k6bry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:mic-square-f" {...props}></Icon>
