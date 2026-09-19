<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aleoypblh.css';
import '../../css/q/qqfcp2vpb.css';
import '../../css/j/j496qmb2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aleoypblh"/><ellipse class="qqfcp2vpb"/><ellipse class="j496qmb2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:mask" {...props}></Icon>
