<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ryk7c9tyn.css';
import '../../css/r/rv64cqbog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ryk7c9tyn"/><path class="rv64cqbog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:joystick-alt" {...props}></Icon>
