<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iij3ykbwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iij3ykbwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:netgoat-light" {...props}></Icon>
