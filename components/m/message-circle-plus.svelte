<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yr3vlkb3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yr3vlkb3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:message-circle-plus" {...props}></Icon>
