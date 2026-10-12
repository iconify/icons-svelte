<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6xnjzbga.css';
import '../../css/k/k7by-rbvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j6xnjzbga"/><path clip-rule="evenodd" class="k7by-rbvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:map-pinned-filled" {...props}></Icon>
