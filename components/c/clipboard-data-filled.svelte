<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gw9reep1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gw9reep1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:clipboard-data-filled" {...props}></Icon>
