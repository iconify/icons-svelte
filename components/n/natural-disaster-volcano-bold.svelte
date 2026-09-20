<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxy3cpb-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rxy3cpb-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:natural-disaster-volcano-bold" {...props}></Icon>
