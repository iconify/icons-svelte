<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kog5zicjb.css';
import '../../css/y/y02bymb-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="kog5zicjb"/><path class="y02bymb-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:commento" {...props}></Icon>
