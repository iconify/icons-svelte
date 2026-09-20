<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k785w0v7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k785w0v7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:automatic-gate-up-outline" {...props}></Icon>
