<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ik25i8w8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="ik25i8w8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:pigpenh" {...props}></Icon>
