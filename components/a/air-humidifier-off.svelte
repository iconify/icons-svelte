<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbk7ft81q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bbk7ft81q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:air-humidifier-off" {...props}></Icon>
