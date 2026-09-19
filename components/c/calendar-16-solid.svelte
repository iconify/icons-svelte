<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xw5f-kbku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xw5f-kbku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:calendar-16-solid" {...props}></Icon>
