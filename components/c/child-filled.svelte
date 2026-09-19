<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/quhy5abwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="quhy5abwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:child-filled" {...props}></Icon>
