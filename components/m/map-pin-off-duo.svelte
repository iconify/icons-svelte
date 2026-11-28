<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0r16e4cs.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/w/wp1q2ntpc.css';
import '../../css/y/yylyrccfn.css';
import '../../css/q/qjzyurbpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i0r16e4cs secondary"/><g class="dt0cm9dhy primary"><path class="wp1q2ntpc"/><path class="yylyrccfn"/><path class="qjzyurbpi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:map-pin-off-duo" {...props}></Icon>
