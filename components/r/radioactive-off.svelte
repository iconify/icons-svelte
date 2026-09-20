<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zm8s9bcod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zm8s9bcod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:radioactive-off" {...props}></Icon>
