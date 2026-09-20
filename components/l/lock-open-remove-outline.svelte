<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tj52in7tj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tj52in7tj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:lock-open-remove-outline" {...props}></Icon>
