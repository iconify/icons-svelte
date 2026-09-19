<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/skg2cobse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="skg2cobse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:release-definition" {...props}></Icon>
