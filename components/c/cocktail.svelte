<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r__zncc8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":24};
const content = `<path class="r__zncc8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:cocktail" {...props}></Icon>
