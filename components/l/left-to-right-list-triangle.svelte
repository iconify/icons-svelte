<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yl1efpbyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yl1efpbyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:left-to-right-list-triangle" {...props}></Icon>
