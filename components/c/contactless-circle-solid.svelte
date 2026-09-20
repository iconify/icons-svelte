<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkez5lb6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wkez5lb6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:contactless-circle-solid" {...props}></Icon>
