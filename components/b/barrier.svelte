<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_8zmqbtg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="i_8zmqbtg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:barrier" {...props}></Icon>
