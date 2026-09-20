<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fz4cpybds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="fz4cpybds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:pencil" {...props}></Icon>
