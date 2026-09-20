<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wruy1ebcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wruy1ebcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:arrow-down-waves-solid" {...props}></Icon>
