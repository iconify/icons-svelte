<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbkwmk22y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bbkwmk22y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:house-floor-b" {...props}></Icon>
