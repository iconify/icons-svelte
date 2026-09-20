<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pu1kso72z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pu1kso72z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:fortress" {...props}></Icon>
