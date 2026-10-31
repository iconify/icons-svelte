<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/daum-jwra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="daum-jwra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:factory-gloss" {...props}></Icon>
