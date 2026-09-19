<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7misdb5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":384};
const content = `<path class="n7misdb5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:format-subject" {...props}></Icon>
