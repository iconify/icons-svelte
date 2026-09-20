<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z256i1gov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z256i1gov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:gauge-empty" {...props}></Icon>
