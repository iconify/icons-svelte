<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fj0x7hbrj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="fj0x7hbrj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:maki" {...props}></Icon>
