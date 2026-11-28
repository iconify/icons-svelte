<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ea5taoauh.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/y/ymq-jv4ji.css';
import '../../css/q/qjzyurbpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ea5taoauh secondary"/><g class="dt0cm9dhy primary"><path class="ymq-jv4ji"/><path class="qjzyurbpi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:heart-off-duo" {...props}></Icon>
