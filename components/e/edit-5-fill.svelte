<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxwu5qbal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jxwu5qbal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:edit-5-fill" {...props}></Icon>
