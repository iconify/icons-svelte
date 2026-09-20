<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rg1-ktdwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="rg1-ktdwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:end-point-diamond-remix" {...props}></Icon>
