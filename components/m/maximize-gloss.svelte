<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wteyjubfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wteyjubfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:maximize-gloss" {...props}></Icon>
