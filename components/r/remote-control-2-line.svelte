<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/el-2dqbav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="el-2dqbav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:remote-control-2-line" {...props}></Icon>
