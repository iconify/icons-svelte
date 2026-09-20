<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6vb6pbtd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q6vb6pbtd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:nest-thermostat" {...props}></Icon>
