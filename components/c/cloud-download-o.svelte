<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ridq9kr5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ridq9kr5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:cloud-download-o" {...props}></Icon>
