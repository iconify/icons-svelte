<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6unurbwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g6unurbwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:nimrod" {...props}></Icon>
