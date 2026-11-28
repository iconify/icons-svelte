<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/e/ekf8t7boi.css';
import '../../css/j/jmgrsengl.css';
import '../../css/y/y09vs8_da.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ekf8t7boi"/><path class="jmgrsengl"/><path class="y09vs8_da"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:heart-handshake" {...props}></Icon>
