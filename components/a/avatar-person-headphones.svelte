<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/j/jnmyo5jwp.css';
import '../../css/d/d3y9mw6db.css';
import '../../css/q/q6hphdz7k.css';
import '../../css/y/ysbsdobug.css';
import '../../css/x/xvjipzb1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="jnmyo5jwp"/><path class="d3y9mw6db"/><path class="q6hphdz7k wm-a"/><path class="wm-a ysbsdobug"/><path class="wm-a xvjipzb1h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:avatar-person-headphones" {...props}></Icon>
