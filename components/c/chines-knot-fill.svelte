<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/b/b52jpbbmn.css';
import '../../css/w/w-s1ovkba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="bi12bsetm"><path class="b52jpbbmn"/><path class="w-s1ovkba"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chines-knot-fill" {...props}></Icon>
