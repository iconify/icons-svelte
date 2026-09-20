<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xos-9pjzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xos-9pjzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:download" {...props}></Icon>
