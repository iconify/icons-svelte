<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fs_v2rb9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fs_v2rb9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:annoyed-line" {...props}></Icon>
