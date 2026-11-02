<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pg8ftccam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pg8ftccam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:earth-fill" {...props}></Icon>
