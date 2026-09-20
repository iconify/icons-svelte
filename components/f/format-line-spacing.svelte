<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oup0wabdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oup0wabdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-line-spacing" {...props}></Icon>
