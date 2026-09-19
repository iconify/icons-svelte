<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hc0-s1bju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":960,"height":993};
const content = `<path class="hc0-s1bju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:moneybag" {...props}></Icon>
