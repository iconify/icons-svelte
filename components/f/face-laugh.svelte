<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djznmdbho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="djznmdbho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:face-laugh" {...props}></Icon>
