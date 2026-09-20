<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kr0fxhktn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kr0fxhktn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:caret-up" {...props}></Icon>
