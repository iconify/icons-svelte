<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_osqir4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t_osqir4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:lto" {...props}></Icon>
