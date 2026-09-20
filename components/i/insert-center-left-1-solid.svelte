<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/faid7gmwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="faid7gmwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:insert-center-left-1-solid" {...props}></Icon>
