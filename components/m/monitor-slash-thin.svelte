<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nr3ujtb4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="nr3ujtb4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:monitor-slash-thin" {...props}></Icon>
