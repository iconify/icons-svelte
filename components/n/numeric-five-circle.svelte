<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdkry4kfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gdkry4kfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:numeric-five-circle" {...props}></Icon>
