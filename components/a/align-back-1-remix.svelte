<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdx71ndkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="vdx71ndkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:align-back-1-remix" {...props}></Icon>
