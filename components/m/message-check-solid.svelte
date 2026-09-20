<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sx0ez053t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sx0ez053t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:message-check-solid" {...props}></Icon>
