<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/veec_dbhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="veec_dbhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:image-description" {...props}></Icon>
