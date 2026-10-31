<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utdba5xyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="utdba5xyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:folder-download-corner-fill-round" {...props}></Icon>
