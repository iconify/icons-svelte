<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aiyr2hb8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aiyr2hb8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clipboard-remove-outline" {...props}></Icon>
