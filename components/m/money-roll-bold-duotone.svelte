<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrk4-orkz.css';
import '../../css/u/u15giqb2e.css';
import '../../css/q/qryzuxmyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yrk4-orkz"/><path class="u15giqb2e"/><path class="qryzuxmyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:money-roll-bold-duotone" {...props}></Icon>
