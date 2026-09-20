<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/javv36f_m.css';
import '../../css/s/s44bm75jf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="javv36f_m"/><path class="s44bm75jf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:launch-go-bold" {...props}></Icon>
