<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km50ekb7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="km50ekb7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrows-pointing-out" {...props}></Icon>
