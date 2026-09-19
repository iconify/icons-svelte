<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tom5xu4iv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":24};
const content = `<path class="tom5xu4iv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:cursor" {...props}></Icon>
