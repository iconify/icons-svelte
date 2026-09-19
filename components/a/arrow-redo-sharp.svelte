<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ya4px7blt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ya4px7blt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:arrow-redo-sharp" {...props}></Icon>
