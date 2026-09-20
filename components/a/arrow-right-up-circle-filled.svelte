<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tecmeuo1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tecmeuo1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:arrow-right-up-circle-filled" {...props}></Icon>
