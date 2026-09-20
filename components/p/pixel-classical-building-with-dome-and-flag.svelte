<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nns_4vajp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nns_4vajp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pixel-classical-building-with-dome-and-flag" {...props}></Icon>
