<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_tc7vb2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="g_tc7vb2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:list-bullet-below-rectangle" {...props}></Icon>
