<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgu1w2bgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":528};
const content = `<path class="fgu1w2bgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:home" {...props}></Icon>
