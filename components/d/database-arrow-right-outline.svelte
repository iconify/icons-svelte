<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-fpd76-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-fpd76-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:database-arrow-right-outline" {...props}></Icon>
