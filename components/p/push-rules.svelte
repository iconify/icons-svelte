<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ir-wcidyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ir-wcidyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:push-rules" {...props}></Icon>
