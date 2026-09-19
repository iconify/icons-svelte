<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/orpglcbbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":508,"height":512};
const content = `<path class="orpglcbbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:csound" {...props}></Icon>
