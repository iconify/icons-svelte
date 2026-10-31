<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aj046jq3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aj046jq3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:file-text-round" {...props}></Icon>
