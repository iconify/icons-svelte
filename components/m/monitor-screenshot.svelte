<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbhw0nleb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gbhw0nleb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:monitor-screenshot" {...props}></Icon>
