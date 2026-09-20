<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/doadbp5_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="doadbp5_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:fine-tune-solid" {...props}></Icon>
