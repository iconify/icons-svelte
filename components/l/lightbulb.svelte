<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pe5v8pcuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="pe5v8pcuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:lightbulb" {...props}></Icon>
