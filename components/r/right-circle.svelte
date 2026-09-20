<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x359nsadw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x359nsadw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:right-circle" {...props}></Icon>
