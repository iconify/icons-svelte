<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sfjf88b7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sfjf88b7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:outbox" {...props}></Icon>
