<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgmy0ebaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="dgmy0ebaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:folder-checked" {...props}></Icon>
