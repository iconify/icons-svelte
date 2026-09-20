<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sm7h6xalq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sm7h6xalq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:parking-lights-line" {...props}></Icon>
