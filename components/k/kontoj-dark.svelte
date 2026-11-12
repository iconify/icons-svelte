<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlgf8l19l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vlgf8l19l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kontoj-dark" {...props}></Icon>
