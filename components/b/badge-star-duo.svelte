<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djhm11b9z.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/l4--ovbba.css';
import '../../css/x/xeq28t4zp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="djhm11b9z secondary"/><g class="dt0cm9dhy primary"><path class="l4--ovbba"/><path class="xeq28t4zp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:badge-star-duo" {...props}></Icon>
