<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3cim7bff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x3cim7bff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alpha-s-circle-outline" {...props}></Icon>
