<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnzk4yoqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="tnzk4yoqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:lightbulb" {...props}></Icon>
