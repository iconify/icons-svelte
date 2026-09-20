<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/an2x7zf5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="an2x7zf5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:desktop-filled" {...props}></Icon>
