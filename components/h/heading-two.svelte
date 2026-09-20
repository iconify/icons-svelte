<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlp4ho8vz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wlp4ho8vz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:heading-two" {...props}></Icon>
