<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p800uf9hd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p800uf9hd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:checkio" {...props}></Icon>
