<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d56pwb11w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="d56pwb11w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:diamonds-symbol-flat" {...props}></Icon>
