<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5ejsiyni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d5ejsiyni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alpha-u-circle" {...props}></Icon>
