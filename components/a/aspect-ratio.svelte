<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kf4uuwbti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="kf4uuwbti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:aspect-ratio" {...props}></Icon>
