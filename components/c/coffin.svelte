<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbebmxbvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qbebmxbvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:coffin" {...props}></Icon>
