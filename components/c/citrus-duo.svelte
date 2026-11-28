<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-gk01bni.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/c/cqp1zj20f.css';
import '../../css/g/ghgl7wbcz.css';
import '../../css/y/yoox92wcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h-gk01bni secondary"/><g class="dt0cm9dhy primary"><path class="cqp1zj20f"/><path class="ghgl7wbcz"/><path class="yoox92wcb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:citrus-duo" {...props}></Icon>
