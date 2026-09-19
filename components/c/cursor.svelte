<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ziyq9ys9s.css';
import '../../css/q/qgoa3-pny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path transform="matrix(.92099 0 0 .92169 -.41 .382)" class="ziyq9ys9s"/><path class="qgoa3-pny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:cursor" {...props}></Icon>
