<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usb52b63m.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/imwmxwxdg.css';
import '../../css/p/p5yi_xv5c.css';
import '../../css/b/b0zv3cjwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="secondary usb52b63m"/><g class="dt0cm9dhy primary"><path class="imwmxwxdg"/><path class="p5yi_xv5c"/><path class="b0zv3cjwz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ease-out-duo" {...props}></Icon>
