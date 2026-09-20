<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pyu-_xuoe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="pyu-_xuoe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:apple" {...props}></Icon>
