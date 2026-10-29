<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-7s1tbdr.css';
import '../../css/d/ds0uwvbso.css';
import '../../css/t/te1bgvv9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-shadow y-7s1tbdr"/><path class="ds0uwvbso wm-k"/><path class="te1bgvv9h wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-pastel:chevron-right" {...props}></Icon>
