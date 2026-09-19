<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5vd25u4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":35,"height":24};
const content = `<path class="u5vd25u4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:laravel" {...props}></Icon>
