<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/r/rgpbbbb1c.css';
import '../../css/j/j2fajacou.css';
import '../../css/t/tg3ffvmkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rgpbbbb1c"/><path class="j2fajacou"/><path class="tg3ffvmkc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:paint-brush-line-duotone" {...props}></Icon>
