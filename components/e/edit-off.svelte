<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/l37l5sboh.css';
import '../../css/u/uj_mr6b0o.css';
import '../../css/q/qjzyurbpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="l37l5sboh"/><path class="uj_mr6b0o"/><path class="qjzyurbpi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:edit-off" {...props}></Icon>
