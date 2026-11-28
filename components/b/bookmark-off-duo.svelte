<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a25g90ajj.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/y/yz09xbcvb.css';
import '../../css/q/qjzyurbpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a25g90ajj secondary"/><g class="dt0cm9dhy primary"><path class="yz09xbcvb"/><path class="qjzyurbpi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:bookmark-off-duo" {...props}></Icon>
