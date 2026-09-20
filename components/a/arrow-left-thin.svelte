<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4dc6ybvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b4dc6ybvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-left-thin" {...props}></Icon>
