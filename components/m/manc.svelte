<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/os2j4ybkr.css';
import '../../css/r/r2-u52t_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="os2j4ybkr"/><path class="r2-u52t_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:manc" {...props}></Icon>
