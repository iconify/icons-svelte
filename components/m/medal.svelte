<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gsw-e1bdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gsw-e1bdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:medal" {...props}></Icon>
