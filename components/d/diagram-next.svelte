<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xotfa1b4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="xotfa1b4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:diagram-next" {...props}></Icon>
