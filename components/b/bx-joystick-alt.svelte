<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/alqc54g4m.css';
import '../../css/r/rn2kcz5al.css';
import '../../css/e/eo3krlb4g.css';
import '../../css/g/gnea6-e5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="alqc54g4m"/><circle class="rn2kcz5al"/><path class="eo3krlb4g"/><path class="gnea6-e5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-joystick-alt" {...props}></Icon>
