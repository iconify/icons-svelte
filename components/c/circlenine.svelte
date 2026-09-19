<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fitr7gb4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="fitr7gb4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:circlenine" {...props}></Icon>
