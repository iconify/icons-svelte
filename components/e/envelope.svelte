<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8zf1xq5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1408};
const content = `<path class="g8zf1xq5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:envelope" {...props}></Icon>
