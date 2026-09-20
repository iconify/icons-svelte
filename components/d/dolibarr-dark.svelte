<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvczsfb5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bvczsfb5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dolibarr-dark" {...props}></Icon>
