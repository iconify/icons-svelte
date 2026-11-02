<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oaifu8bmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oaifu8bmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flag-1-fill" {...props}></Icon>
