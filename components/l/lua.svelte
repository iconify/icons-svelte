<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6c6d7t2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p6c6d7t2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:lua" {...props}></Icon>
