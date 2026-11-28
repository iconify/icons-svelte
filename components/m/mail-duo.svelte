<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igi5v8bda.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/q/qxqm7i1xs.css';
import '../../css/p/pp1fe4bxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="igi5v8bda secondary"/><g class="dt0cm9dhy primary"><path class="qxqm7i1xs"/><path class="pp1fe4bxb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:mail-duo" {...props}></Icon>
