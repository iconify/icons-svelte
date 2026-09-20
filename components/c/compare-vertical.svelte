<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0f5iobdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o0f5iobdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:compare-vertical" {...props}></Icon>
