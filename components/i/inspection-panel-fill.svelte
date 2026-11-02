<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqz_x-bzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tqz_x-bzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:inspection-panel-fill" {...props}></Icon>
