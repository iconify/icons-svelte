<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-s12niqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="x-s12niqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:heart-cross-remix" {...props}></Icon>
