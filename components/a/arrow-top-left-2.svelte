<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivxjur8vk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ivxjur8vk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-top-left-2" {...props}></Icon>
