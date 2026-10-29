<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uo-2b4bms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uo-2b4bms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:door-open-solid" {...props}></Icon>
