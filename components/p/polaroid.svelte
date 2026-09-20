<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fht-kwr4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fht-kwr4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:polaroid" {...props}></Icon>
