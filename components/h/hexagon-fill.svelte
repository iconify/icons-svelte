<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-g4gacxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="e-g4gacxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:hexagon-fill" {...props}></Icon>
