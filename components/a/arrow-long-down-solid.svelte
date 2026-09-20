<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qv3oglbmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qv3oglbmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:arrow-long-down-solid" {...props}></Icon>
