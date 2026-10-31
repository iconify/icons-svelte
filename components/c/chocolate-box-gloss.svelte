<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/faxv8eb7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="faxv8eb7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:chocolate-box-gloss" {...props}></Icon>
