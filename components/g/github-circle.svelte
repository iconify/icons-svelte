<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/l133d9p_s.css';
import '../../css/o/oasgoj2dk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<g class="cuyn6tgcc"><path class="l133d9p_s"/><path class="oasgoj2dk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:github-circle" {...props}></Icon>
