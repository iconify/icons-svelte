<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/h/hz38l9bau.css';
import '../../css/b/bhse_2bgx.css';
import '../../css/v/v509wnbnq.css';
import '../../css/r/r7ac2ob5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><rect class="hz38l9bau"/><rect class="bhse_2bgx"/><rect class="v509wnbnq"/><path class="r7ac2ob5u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:network-solid" {...props}></Icon>
