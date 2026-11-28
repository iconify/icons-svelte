<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6tq2ccnj.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/v/vltn-2bvp.css';
import '../../css/g/gk43m7bjx.css';
import '../../css/e/exgf0m5uh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary u6tq2ccnj"/><g class="dt0cm9dhy primary"><path class="vltn-2bvp"/><path class="gk43m7bjx"/><path class="exgf0m5uh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:external-link-duo" {...props}></Icon>
