<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/s/symvdirkk.css';
import '../../css/m/mo-m0vn9j.css';
import '../../css/f/ftu19bcfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="symvdirkk"/><path class="mo-m0vn9j"/><path class="ftu19bcfd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:car-2-flat" {...props}></Icon>
