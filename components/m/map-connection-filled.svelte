<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvmy2nbtz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dvmy2nbtz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:map-connection-filled" {...props}></Icon>
