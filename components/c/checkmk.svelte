<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmz9v2xcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jmz9v2xcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:checkmk" {...props}></Icon>
