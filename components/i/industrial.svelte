<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s95_udnar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s95_udnar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:industrial" {...props}></Icon>
