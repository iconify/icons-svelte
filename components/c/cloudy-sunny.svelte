<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nifwvfbde.css';
import '../../css/v/vx-ffrb6n.css';
import '../../css/q/q3c6h8-rl.css';
import '../../css/s/sh325x39x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="nifwvfbde"/><path class="vx-ffrb6n"/><path class="q3c6h8-rl"/><path class="sh325x39x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:cloudy-sunny" {...props}></Icon>
