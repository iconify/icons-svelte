<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcgau3xpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zcgau3xpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:package-gloss" {...props}></Icon>
