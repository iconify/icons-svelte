<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oud9o5bru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oud9o5bru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:hard-drive-3-line" {...props}></Icon>
