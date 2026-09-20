<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1ax39u0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t1ax39u0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chevron-down-right-waves-solid" {...props}></Icon>
