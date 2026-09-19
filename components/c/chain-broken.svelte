<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/di2cjrb4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1664};
const content = `<path class="di2cjrb4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:chain-broken" {...props}></Icon>
