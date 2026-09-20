<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfc3um3-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kfc3um3-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:ccleaner" {...props}></Icon>
