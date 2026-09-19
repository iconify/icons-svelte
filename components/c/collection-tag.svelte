<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf_n_km6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="yf_n_km6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:collection-tag" {...props}></Icon>
