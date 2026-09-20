<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to9c7bclz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="to9c7bclz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:chat-settings-line" {...props}></Icon>
