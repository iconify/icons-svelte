<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgyb_l4ec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sgyb_l4ec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:exclude-solid" {...props}></Icon>
