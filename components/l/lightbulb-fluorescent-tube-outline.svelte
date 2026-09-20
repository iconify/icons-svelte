<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2i7u1bkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d2i7u1bkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:lightbulb-fluorescent-tube-outline" {...props}></Icon>
