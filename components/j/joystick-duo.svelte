<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ax6fwmbjw.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/r/r1j4lk9ap.css';
import '../../css/c/clku-lbrt.css';
import '../../css/s/srnt8ebvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ax6fwmbjw secondary"/><g class="dt0cm9dhy primary"><path class="r1j4lk9ap"/><circle class="clku-lbrt"/><path class="srnt8ebvz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:joystick-duo" {...props}></Icon>
