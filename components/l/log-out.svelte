<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/x/xreczbeld.css';
import '../../css/s/s_o0tcy8i.css';
import '../../css/l/ladxk0btf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="xreczbeld"/><path class="s_o0tcy8i"/><path class="ladxk0btf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:log-out" {...props}></Icon>
