<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxcwqhbry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zxcwqhbry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chart-no-axes-column" {...props}></Icon>
