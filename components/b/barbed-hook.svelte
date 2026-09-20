<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0w312bli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="q0w312bli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:barbed-hook" {...props}></Icon>
