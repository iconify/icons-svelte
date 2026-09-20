<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2-9esben.css';
import '../../css/w/w04o84byj.css';
import '../../css/d/dwzrjlbiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u2-9esben"/><path class="w04o84byj"/><path class="dwzrjlbiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:analytics-bars-3-d-bold" {...props}></Icon>
