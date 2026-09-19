<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/s/shu3xdl9q.css';
import '../../css/l/l5i5hyb3b.css';
import '../../css/o/ozd_fxwmk.css';
import '../../css/k/k6cs5ab0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><circle class="shu3xdl9q"/><path class="l5i5hyb3b"/><path class="ozd_fxwmk"/><path class="k6cs5ab0y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:refresh-circular" {...props}></Icon>
