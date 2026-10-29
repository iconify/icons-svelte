<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/k0tm63b0s.css';
import '../../css/v/vvmccbmmh.css';
import '../../css/p/phawmubhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="k0tm63b0s"/><path class="vvmccbmmh"/><path class="phawmubhy wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:paintbrush" {...props}></Icon>
