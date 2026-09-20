<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tr4n1vk1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tr4n1vk1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:bookmark-duotone" {...props}></Icon>
