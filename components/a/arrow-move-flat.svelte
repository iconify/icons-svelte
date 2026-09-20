<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6fqfab6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="o6fqfab6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:arrow-move-flat" {...props}></Icon>
