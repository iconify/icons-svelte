<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/an_jw_blg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1025};
const content = `<path class="an_jw_blg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:plantalt" {...props}></Icon>
