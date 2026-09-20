<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r60m7nbug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r60m7nbug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chart-line-up-fill" {...props}></Icon>
