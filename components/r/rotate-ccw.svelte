<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzudws-br.css';
import '../../css/n/nnhz2fbfy.css';
import '../../css/f/f26-q2vvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hzudws-br wm-shadow"/><path class="nnhz2fbfy wm-k"/><path class="f26-q2vvv wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-pastel:rotate-ccw" {...props}></Icon>
