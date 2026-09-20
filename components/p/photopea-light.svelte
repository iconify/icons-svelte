<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5y1f8b5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d5y1f8b5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:photopea-light" {...props}></Icon>
