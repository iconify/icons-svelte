<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jajn8kada.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jajn8kada"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:food-menu" {...props}></Icon>
