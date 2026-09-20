<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikdh51bms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ikdh51bms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:face-scan-1" {...props}></Icon>
