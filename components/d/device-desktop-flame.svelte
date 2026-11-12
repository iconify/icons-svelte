<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anp7lrczn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="anp7lrczn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-desktop-flame" {...props}></Icon>
