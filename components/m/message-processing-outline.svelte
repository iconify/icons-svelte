<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhv7hepxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hhv7hepxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:message-processing-outline" {...props}></Icon>
