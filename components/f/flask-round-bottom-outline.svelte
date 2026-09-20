<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8nwzebsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j8nwzebsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:flask-round-bottom-outline" {...props}></Icon>
