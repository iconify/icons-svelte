<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbst8fbyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kbst8fbyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:buggregator-dark" {...props}></Icon>
