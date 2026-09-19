<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_g4ftbrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="o_g4ftbrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:lifefull" {...props}></Icon>
