<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfo94lbhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kfo94lbhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:book-time" {...props}></Icon>
