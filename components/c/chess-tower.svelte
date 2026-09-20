<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/go0obobxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="go0obobxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:chess-tower" {...props}></Icon>
