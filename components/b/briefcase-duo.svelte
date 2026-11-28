<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mkck_91nn.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/i-ikzyb4j.css';
import '../../css/o/ox7v1pb2u.css';
import '../../css/q/q7r63ij4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mkck_91nn secondary"/><g class="dt0cm9dhy primary"><path class="i-ikzyb4j"/><path class="ox7v1pb2u"/><path class="q7r63ij4m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:briefcase-duo" {...props}></Icon>
