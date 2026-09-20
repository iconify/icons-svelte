<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/feh3568qk.css';
import '../../css/s/se175u0vt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="feh3568qk"/><path clip-rule="evenodd" class="se175u0vt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:aas-shell-search-filled" {...props}></Icon>
