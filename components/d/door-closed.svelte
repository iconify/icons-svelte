<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2zq-9byz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="c2zq-9byz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:door-closed" {...props}></Icon>
