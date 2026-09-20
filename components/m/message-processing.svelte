<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkzas_28k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vkzas_28k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:message-processing" {...props}></Icon>
