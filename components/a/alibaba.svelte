<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mj8eq7bqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mj8eq7bqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:alibaba" {...props}></Icon>
