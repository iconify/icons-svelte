<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vj264xb_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vj264xb_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:heading-5-solid" {...props}></Icon>
