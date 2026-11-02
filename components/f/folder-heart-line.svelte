<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjng15r9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pjng15r9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-heart-line" {...props}></Icon>
