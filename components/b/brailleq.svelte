<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxs6jfbzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="fxs6jfbzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:brailleq" {...props}></Icon>
