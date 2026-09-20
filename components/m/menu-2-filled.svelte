<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fi9pjnbgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fi9pjnbgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:menu-2-filled" {...props}></Icon>
