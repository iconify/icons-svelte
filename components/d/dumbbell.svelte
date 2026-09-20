<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hi6s0tcxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hi6s0tcxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:dumbbell" {...props}></Icon>
