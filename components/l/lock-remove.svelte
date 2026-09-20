<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahiw1-bap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ahiw1-bap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:lock-remove" {...props}></Icon>
