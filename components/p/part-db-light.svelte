<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_ckomb5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y_ckomb5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:part-db-light" {...props}></Icon>
