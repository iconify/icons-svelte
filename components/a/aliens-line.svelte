<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsaa8ob7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dsaa8ob7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:aliens-line" {...props}></Icon>
