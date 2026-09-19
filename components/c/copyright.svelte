<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2514ubjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="y2514ubjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:copyright" {...props}></Icon>
