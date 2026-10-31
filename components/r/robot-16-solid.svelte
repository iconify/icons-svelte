<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkbykbcth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pkbykbcth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:robot-16-solid" {...props}></Icon>
