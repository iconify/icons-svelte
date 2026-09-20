<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3l_-nv0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="l3l_-nv0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:brightness-3-solid" {...props}></Icon>
