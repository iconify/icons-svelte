<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/byqra4-jw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="byqra4-jw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:microphone-filled" {...props}></Icon>
