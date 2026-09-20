<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mc4m0ib3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mc4m0ib3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:apple-podcasts-light" {...props}></Icon>
