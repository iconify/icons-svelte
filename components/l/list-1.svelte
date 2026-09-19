<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rktrmjtat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":24};
const content = `<path class="rktrmjtat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:list-1" {...props}></Icon>
