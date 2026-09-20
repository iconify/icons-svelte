<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru8eoqtct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ru8eoqtct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:apostrophecms-dark" {...props}></Icon>
