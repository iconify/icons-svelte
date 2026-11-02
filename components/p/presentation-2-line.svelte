<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_5l9nbkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d_5l9nbkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:presentation-2-line" {...props}></Icon>
