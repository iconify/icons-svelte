<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zo60vmb-f.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/g1akucbjg.css';
import '../../css/k/ky0-5j8-r.css';
import '../../css/g/gcmcpc6kt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary zo60vmb-f"/><g class="dt0cm9dhy primary"><path class="g1akucbjg"/><path class="ky0-5j8-r"/><path class="gcmcpc6kt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:bed-duo" {...props}></Icon>
