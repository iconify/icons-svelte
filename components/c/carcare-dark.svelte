<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgxsjub5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rgxsjub5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:carcare-dark" {...props}></Icon>
