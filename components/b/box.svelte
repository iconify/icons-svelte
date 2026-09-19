<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmhxj5bon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":740,"height":750};
const content = `<path class="xmhxj5bon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:box" {...props}></Icon>
