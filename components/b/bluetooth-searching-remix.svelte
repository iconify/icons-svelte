<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o16krccwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="o16krccwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:bluetooth-searching-remix" {...props}></Icon>
