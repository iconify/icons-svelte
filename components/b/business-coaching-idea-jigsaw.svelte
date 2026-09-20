<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbhx33-fu.css';
import '../../css/i/iy9nx5bhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rbhx33-fu"/><path class="iy9nx5bhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:business-coaching-idea-jigsaw" {...props}></Icon>
