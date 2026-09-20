<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7gqgkb3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m7gqgkb3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:lightbulb-on-10" {...props}></Icon>
