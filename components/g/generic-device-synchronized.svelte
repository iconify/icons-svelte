<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eb5cvdbag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eb5cvdbag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:generic-device-synchronized" {...props}></Icon>
