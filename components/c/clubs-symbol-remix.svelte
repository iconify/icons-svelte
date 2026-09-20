<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d42i0vmjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="d42i0vmjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:clubs-symbol-remix" {...props}></Icon>
