<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hx5pt5wxs.css';
import '../../css/d/drdla2-9e.css';
import '../../css/w/wdin9-bzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hx5pt5wxs"/><circle class="drdla2-9e"/><circle class="wdin9-bzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-taxi" {...props}></Icon>
