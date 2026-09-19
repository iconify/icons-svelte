<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkclmjbym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pkclmjbym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:download-circle-filled" {...props}></Icon>
