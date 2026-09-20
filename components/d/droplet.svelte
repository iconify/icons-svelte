<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/as-y2cceh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="as-y2cceh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:droplet" {...props}></Icon>
