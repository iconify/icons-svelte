<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ef8_ic69j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ef8_ic69j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:picpeak" {...props}></Icon>
