<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lq85roq9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lq85roq9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:jotty-light" {...props}></Icon>
