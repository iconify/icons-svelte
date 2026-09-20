<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msngx6wzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="msngx6wzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-list-2-fill" {...props}></Icon>
