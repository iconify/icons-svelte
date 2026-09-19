<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usx-1ledh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="usx-1ledh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:indent-right" {...props}></Icon>
