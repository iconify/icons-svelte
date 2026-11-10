<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zw7xwxbgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zw7xwxbgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:diagram-flow-horizontal-filled" {...props}></Icon>
