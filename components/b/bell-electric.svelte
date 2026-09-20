<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/z/zr6myfbli.css';
import '../../css/c/cnc8kxp4p.css';
import '../../css/o/o3jl589pi.css';
import '../../css/g/gl_t73bxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zr6myfbli"/><circle class="cnc8kxp4p"/><circle class="o3jl589pi"/><rect class="gl_t73bxh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:bell-electric" {...props}></Icon>
