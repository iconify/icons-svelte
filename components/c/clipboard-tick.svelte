<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4w25gb8w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x4w25gb8w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clipboard-tick" {...props}></Icon>
