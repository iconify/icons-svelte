<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-d65nber.css';
import '../../css/j/je17xlb_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="p-d65nber"/><path class="je17xlb_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:folder-lock" {...props}></Icon>
