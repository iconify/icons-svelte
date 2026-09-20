<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f0nmc9b2i.css';
import '../../css/m/mvd1tt_en.css';
import '../../css/o/o_kf6bbyz.css';
import '../../css/a/a80uv-e5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="f0nmc9b2i"/><path class="mvd1tt_en"/><path class="o_kf6bbyz"/><path class="a80uv-e5n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:chimney-2" {...props}></Icon>
