<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ph08xqbao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ph08xqbao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:list-tree-fill-round" {...props}></Icon>
