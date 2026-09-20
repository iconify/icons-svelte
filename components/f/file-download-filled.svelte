<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-g932nak.css';
import '../../css/p/pt1jbnbuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f-g932nak"/><path class="pt1jbnbuw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:file-download-filled" {...props}></Icon>
