<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyja_c0px.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iyja_c0px"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:rabbit-gloss" {...props}></Icon>
