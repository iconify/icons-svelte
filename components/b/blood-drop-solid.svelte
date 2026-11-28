<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gibrudeyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gibrudeyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:blood-drop-solid" {...props}></Icon>
