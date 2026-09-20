<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4sdadetl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="m4sdadetl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:fork-knife-remix" {...props}></Icon>
