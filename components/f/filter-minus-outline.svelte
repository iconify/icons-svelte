<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eaof11a0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eaof11a0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:filter-minus-outline" {...props}></Icon>
