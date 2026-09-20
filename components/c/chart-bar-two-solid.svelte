<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilrxzmlqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ilrxzmlqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chart-bar-two-solid" {...props}></Icon>
