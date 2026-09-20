<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trphc0u7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="trphc0u7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:arrow-long-down-left-solid" {...props}></Icon>
