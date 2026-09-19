<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrji-ib2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="lrji-ib2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:person-skiing-nordic" {...props}></Icon>
