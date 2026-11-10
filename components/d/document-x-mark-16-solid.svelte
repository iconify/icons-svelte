<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ra485_f5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ra485_f5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:document-x-mark-16-solid" {...props}></Icon>
