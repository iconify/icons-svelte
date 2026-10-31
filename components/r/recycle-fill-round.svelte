<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yk8-yaces.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yk8-yaces"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:recycle-fill-round" {...props}></Icon>
