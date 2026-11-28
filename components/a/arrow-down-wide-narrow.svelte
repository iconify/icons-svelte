<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/llap4kbyg.css';
import '../../css/c/ck_7e7hfa.css';
import '../../css/v/vt1ae2bts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="llap4kbyg"/><path class="ck_7e7hfa"/><path class="vt1ae2bts"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-down-wide-narrow" {...props}></Icon>
