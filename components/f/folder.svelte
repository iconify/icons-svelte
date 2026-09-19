<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkenjmbot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":24};
const content = `<path class="vkenjmbot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:folder" {...props}></Icon>
