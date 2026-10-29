<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/lr2qexbim.css';
import '../../css/v/v7jzlzbxs.css';
import '../../css/y/y021bzbie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="lr2qexbim"/><path class="v7jzlzbxs wm-a"/><path class="y021bzbie"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:key-round-duo" {...props}></Icon>
