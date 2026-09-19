<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7vp4achi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s7vp4achi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:no-entry-filled" {...props}></Icon>
