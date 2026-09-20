<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vydw3bcwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vydw3bcwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:elasticsearch-light" {...props}></Icon>
