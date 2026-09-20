<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/au5lyab1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="au5lyab1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-bottom-right" {...props}></Icon>
