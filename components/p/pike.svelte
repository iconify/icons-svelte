<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwbta5htg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="wwbta5htg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:pike" {...props}></Icon>
