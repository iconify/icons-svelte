<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpkqqsb3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="qpkqqsb3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:picture" {...props}></Icon>
