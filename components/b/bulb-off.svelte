<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/je_a-3baf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="je_a-3baf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bulb-off" {...props}></Icon>
