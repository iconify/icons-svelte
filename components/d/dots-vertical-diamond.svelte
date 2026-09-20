<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdmof35ce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vdmof35ce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:dots-vertical-diamond" {...props}></Icon>
