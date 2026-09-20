<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gt1j3xb6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gt1j3xb6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:alpha-c-circle" {...props}></Icon>
