<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipvd7obbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ipvd7obbm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:message-edit" {...props}></Icon>
