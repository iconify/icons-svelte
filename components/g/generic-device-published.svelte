<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4hbolu5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v4hbolu5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:generic-device-published" {...props}></Icon>
