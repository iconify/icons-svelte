<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whg_0cbbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="whg_0cbbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:quiet" {...props}></Icon>
