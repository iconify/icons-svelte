<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8kch-une.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="x8kch-une"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:heart-slash-20-solid" {...props}></Icon>
