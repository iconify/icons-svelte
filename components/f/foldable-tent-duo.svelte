<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3ved-ycr.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/e/ernlo0b2m.css';
import '../../css/z/zkty8cyln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary x3ved-ycr"/><g class="dt0cm9dhy primary"><path class="ernlo0b2m"/><path class="zkty8cyln"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:foldable-tent-duo" {...props}></Icon>
