<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vi22qibhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vi22qibhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-e-diamond-solid" {...props}></Icon>
