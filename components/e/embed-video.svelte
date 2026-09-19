<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-nj7cajn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="g-nj7cajn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:embed-video" {...props}></Icon>
