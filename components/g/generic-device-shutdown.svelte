<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-kfj7bih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x-kfj7bih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:generic-device-shutdown" {...props}></Icon>
