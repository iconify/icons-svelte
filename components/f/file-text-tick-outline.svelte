<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbld0tb0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tbld0tb0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-text-tick-outline" {...props}></Icon>
