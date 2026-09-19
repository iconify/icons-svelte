<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljz9_d-pg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ljz9_d-pg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:merx-ipc-horizon-bullet" {...props}></Icon>
