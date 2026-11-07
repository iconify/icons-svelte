<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czn8j8ltd.css';
import '../../css/g/ga24sqbtj.css';
import '../../css/u/um_zvyb1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="czn8j8ltd"/><path class="ga24sqbtj"/><path clip-rule="evenodd" class="um_zvyb1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-square-warning-outline" {...props}></Icon>
