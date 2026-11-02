<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwdetfb3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lwdetfb3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:gender-trans-16-solid" {...props}></Icon>
