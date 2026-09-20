<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nocrfkt3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nocrfkt3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:envelope-download" {...props}></Icon>
