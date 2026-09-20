<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vv0a2vbww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vv0a2vbww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chevron-left-square-solid" {...props}></Icon>
