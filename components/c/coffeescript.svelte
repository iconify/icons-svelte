<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jh0ih_lld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="jh0ih_lld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:coffeescript" {...props}></Icon>
