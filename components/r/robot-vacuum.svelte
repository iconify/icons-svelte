<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8z-qnb7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f8z-qnb7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:robot-vacuum" {...props}></Icon>
