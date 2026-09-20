<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2kje76tr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k2kje76tr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:folder-lock-line" {...props}></Icon>
