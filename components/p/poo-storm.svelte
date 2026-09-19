<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr59wcg0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="pr59wcg0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:poo-storm" {...props}></Icon>
