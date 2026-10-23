<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xeh-hk-4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xeh-hk-4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:mouth-off" {...props}></Icon>
