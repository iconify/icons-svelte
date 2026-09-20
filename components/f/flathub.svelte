<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihp0-kb6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ihp0-kb6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:flathub" {...props}></Icon>
