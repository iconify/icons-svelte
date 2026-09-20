<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/br0wady_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="br0wady_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-arrows-expand-3-expand-smaller-retract-bigger-big-small-diagonal" {...props}></Icon>
