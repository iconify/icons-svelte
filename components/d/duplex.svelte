<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/o/osd40dbuo.css';
import '../../css/r/rz636hxgh.css';
import '../../css/j/jf0065b9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="osd40dbuo"/><path class="rz636hxgh"/><path class="jf0065b9d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:duplex" {...props}></Icon>
