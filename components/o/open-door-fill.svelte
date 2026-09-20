<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhw_mlbqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hhw_mlbqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:open-door-fill" {...props}></Icon>
