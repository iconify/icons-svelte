<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czy_-bbfy.css';
import '../../css/w/w5btgvbuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="czy_-bbfy"/><path class="w5btgvbuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:downtify" {...props}></Icon>
