<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4tn7uvvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":690};
const content = `<path class="p4tn7uvvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:mixi" {...props}></Icon>
