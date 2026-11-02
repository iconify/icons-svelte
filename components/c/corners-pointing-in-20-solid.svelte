<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gb0rxhbzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="gb0rxhbzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:corners-pointing-in-20-solid" {...props}></Icon>
