<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/z/zlynffbnc.css';
import '../../css/g/g5ly26brs.css';
import '../../css/j/jii3o3xoc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="zlynffbnc"/><path class="g5ly26brs"/><path class="jii3o3xoc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:blood-bag-donation" {...props}></Icon>
