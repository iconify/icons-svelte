<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihebkobli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ihebkobli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:progress-100-line" {...props}></Icon>
