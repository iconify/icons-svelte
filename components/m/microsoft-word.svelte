<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ux5n9jb6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ux5n9jb6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:microsoft-word" {...props}></Icon>
