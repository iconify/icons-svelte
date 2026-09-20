<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfeezi7xs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="cfeezi7xs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:religion-shinto-religion-gate-culture-shinto-japan-japanese-shrine" {...props}></Icon>
