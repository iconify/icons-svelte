<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmdn5gl4d.css';
import '../../css/f/fglfh0u3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wmdn5gl4d"/><path class="fglfh0u3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:bug-filled" {...props}></Icon>
