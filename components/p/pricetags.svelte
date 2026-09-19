<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lf3h5acbj.css';
import '../../css/x/xz6zk-u5v.css';
import '../../css/l/l5rx36btv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":32};
const content = `<g class="cuyn6tgcc"><path class="lf3h5acbj"/><path class="xz6zk-u5v"/><path class="l5rx36btv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:pricetags" {...props}></Icon>
