<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pomm6baka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pomm6baka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:mongoose" {...props}></Icon>
