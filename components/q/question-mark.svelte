<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkawcw3ep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vkawcw3ep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:question-mark" {...props}></Icon>
