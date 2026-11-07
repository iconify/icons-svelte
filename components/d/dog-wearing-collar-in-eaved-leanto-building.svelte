<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqm6qeb7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yqm6qeb7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:dog-wearing-collar-in-eaved-leanto-building" {...props}></Icon>
