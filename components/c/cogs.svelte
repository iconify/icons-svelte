<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qd1aeabyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="qd1aeabyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:cogs" {...props}></Icon>
