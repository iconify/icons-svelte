<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s732qob9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s732qob9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:gas-station-filled" {...props}></Icon>
