<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9b-pgb_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e9b-pgb_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:cellular-signal-0" {...props}></Icon>
