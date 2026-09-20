<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usc8o6-bs.css';
import '../../css/r/rqhj3y1_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="usc8o6-bs"/><path class="rqhj3y1_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:burger-drink" {...props}></Icon>
