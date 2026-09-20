<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmwuo7c7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lmwuo7c7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:info-octagon-solid" {...props}></Icon>
