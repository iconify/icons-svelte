<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m63h_6bsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="m63h_6bsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:line-arrow-rotate-left-2-remix" {...props}></Icon>
