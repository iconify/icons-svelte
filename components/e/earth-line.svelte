<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bt_a2obgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bt_a2obgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:earth-line" {...props}></Icon>
