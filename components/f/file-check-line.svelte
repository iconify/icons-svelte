<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oagmxbsks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oagmxbsks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-check-line" {...props}></Icon>
