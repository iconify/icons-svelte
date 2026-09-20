<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixerqtbkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ixerqtbkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:plus-circle-solid" {...props}></Icon>
