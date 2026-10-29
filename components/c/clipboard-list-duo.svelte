<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/z/zj-cn9tqh.css';
import '../../css/k/kiwgpqb3o.css';
import '../../css/m/mzsw-jb7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="zj-cn9tqh"/><path class="kiwgpqb3o wm-a"/><path class="mzsw-jb7t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:clipboard-list-duo" {...props}></Icon>
