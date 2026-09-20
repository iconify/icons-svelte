<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0s7lfbaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w0s7lfbaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:heading-20-solid" {...props}></Icon>
