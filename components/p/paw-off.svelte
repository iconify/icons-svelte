<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btk6q5xzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="btk6q5xzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:paw-off" {...props}></Icon>
