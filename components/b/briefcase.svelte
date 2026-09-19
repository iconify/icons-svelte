<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w16i9i5vk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="w16i9i5vk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:briefcase" {...props}></Icon>
