<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9hdtjbtt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":24};
const content = `<path class="u9hdtjbtt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:day-lightning" {...props}></Icon>
