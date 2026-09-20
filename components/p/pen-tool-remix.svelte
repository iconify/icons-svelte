<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjq8q_b4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mjq8q_b4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:pen-tool-remix" {...props}></Icon>
