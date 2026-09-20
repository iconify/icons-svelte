<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zkvn7i82x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zkvn7i82x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:keyboard-remix" {...props}></Icon>
