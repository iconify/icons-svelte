<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/l11ovjb-s.css';
import '../../css/q/qw6pybb1f.css';
import '../../css/t/t-bwbsbwy.css';
import '../../css/j/j0tm0dnhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="l11ovjb-s"/><path class="qw6pybb1f"/><path class="t-bwbsbwy"/><path class="j0tm0dnhj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:globe-pin" {...props}></Icon>
