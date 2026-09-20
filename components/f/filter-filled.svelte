<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u51ueuj9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u51ueuj9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:filter-filled" {...props}></Icon>
