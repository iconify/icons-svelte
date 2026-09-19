<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/li9cd2o_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b li9cd2o_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:lichess" {...props}></Icon>
