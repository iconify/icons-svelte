<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3_xu5-hc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h3_xu5-hc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:merge-type" {...props}></Icon>
