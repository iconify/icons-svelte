<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfbl64bcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lfbl64bcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:magic-staff" {...props}></Icon>
