<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iaet4wb5s.css';
import '../../css/z/z43empbta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="iaet4wb5s"/><path class="z43empbta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:picture-in-picture-48-bold" {...props}></Icon>
