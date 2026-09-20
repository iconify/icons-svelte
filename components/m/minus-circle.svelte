<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fu07fk1vk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fu07fk1vk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:minus-circle" {...props}></Icon>
