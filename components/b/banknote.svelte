<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/s/sb-u7hbtr.css';
import '../../css/f/fn1xrabpt.css';
import '../../css/y/yodla97la.css';
import '../../css/k/k-foczbia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="sb-u7hbtr"/><circle class="fn1xrabpt"/><path class="yodla97la"/><path class="k-foczbia"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:banknote" {...props}></Icon>
