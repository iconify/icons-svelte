<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/ya8z-jb5t.css';
import '../../css/o/o0frd8bnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="secondary ya8z-jb5t"/><path class="o0frd8bnv primary"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:cocktail-duotone" {...props}></Icon>
