<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emgvccbua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="emgvccbua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:filter-2" {...props}></Icon>
