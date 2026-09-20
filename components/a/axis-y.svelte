<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vflf7gvne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vflf7gvne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:axis-y" {...props}></Icon>
