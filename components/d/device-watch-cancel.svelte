<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehmlq3b8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ehmlq3b8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-watch-cancel" {...props}></Icon>
