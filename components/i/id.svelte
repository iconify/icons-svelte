<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/y/yjyjkeb1p.css';
import '../../css/z/z_eux7ten.css';
import '../../css/n/nhkxgacuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><rect class="yjyjkeb1p"/><circle class="z_eux7ten"/><path class="nhkxgacuy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:id" {...props}></Icon>
