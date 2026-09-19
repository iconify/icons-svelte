<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rd1sg2zja.css';
import '../../css/z/z-px0kjof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rd1sg2zja"/><path class="z-px0kjof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:power-off" {...props}></Icon>
