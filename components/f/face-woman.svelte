<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nkpu2fbqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nkpu2fbqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:face-woman" {...props}></Icon>
