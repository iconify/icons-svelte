<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vq4imsalu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vq4imsalu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:form-select" {...props}></Icon>
