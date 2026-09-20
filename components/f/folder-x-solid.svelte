<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmtg06bhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="wmtg06bhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:folder-x-solid" {...props}></Icon>
