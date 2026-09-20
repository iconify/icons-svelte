<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1u09r4ws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="d1u09r4ws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:block-2-solid" {...props}></Icon>
