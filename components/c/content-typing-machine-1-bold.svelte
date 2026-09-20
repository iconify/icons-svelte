<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cz5lv6nih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cz5lv6nih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:content-typing-machine-1-bold" {...props}></Icon>
