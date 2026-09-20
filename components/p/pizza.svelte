<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okf185ooe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="okf185ooe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pizza" {...props}></Icon>
