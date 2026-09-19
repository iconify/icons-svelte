<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbho0kbpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="cbho0kbpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:person-dress" {...props}></Icon>
