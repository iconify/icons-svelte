<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/m/mmhfqtz0e.css';
import '../../css/w/w4rw20y0k.css';
import '../../css/i/ijue4lwmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="mmhfqtz0e"/><path class="w4rw20y0k"/><path class="ijue4lwmp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:flask" {...props}></Icon>
