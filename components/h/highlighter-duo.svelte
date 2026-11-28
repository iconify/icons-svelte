<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p27m1gsns.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/o/ox74gzd0h.css';
import '../../css/v/v96i2q43c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p27m1gsns secondary"/><g class="dt0cm9dhy primary"><path class="ox74gzd0h"/><path class="v96i2q43c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:highlighter-duo" {...props}></Icon>
