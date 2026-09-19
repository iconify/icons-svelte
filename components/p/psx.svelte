<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hj10r2b8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="hj10r2b8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:psx" {...props}></Icon>
