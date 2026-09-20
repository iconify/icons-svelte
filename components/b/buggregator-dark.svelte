<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m85i73_cc.css';
import '../../css/c/cj59wwj5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m85i73_cc"/><path class="cj59wwj5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:buggregator-dark" {...props}></Icon>
