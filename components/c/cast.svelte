<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zudyo4p4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":384};
const content = `<path class="zudyo4p4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:cast" {...props}></Icon>
