<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aod6y7ztn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="aod6y7ztn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-up-on-square-20-solid" {...props}></Icon>
