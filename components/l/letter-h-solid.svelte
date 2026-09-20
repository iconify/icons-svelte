<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7465kb8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r7465kb8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-h-solid" {...props}></Icon>
