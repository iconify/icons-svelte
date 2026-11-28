<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqh2lk27i.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/k07fsnbtf.css';
import '../../css/q/qcwlp3baj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cqh2lk27i secondary"/><g class="dt0cm9dhy primary"><path class="k07fsnbtf"/><path class="qcwlp3baj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:key-square-duo" {...props}></Icon>
