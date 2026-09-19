<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzvqbubgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yzvqbubgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:home-heart-filled" {...props}></Icon>
