<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/o0l0yrncv.css';
import '../../css/y/ye7qo4bza.css';
import '../../css/y/yhu770tis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="o0l0yrncv"/><path class="ye7qo4bza"/><path class="yhu770tis"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:posts-carousel-vertical-bold" {...props}></Icon>
