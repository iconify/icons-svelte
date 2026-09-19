<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i72vq7bjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i72vq7bjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-git-pull-request" {...props}></Icon>
