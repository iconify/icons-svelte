<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4dvq9b6o.css';
import '../../css/n/n_2kbbb6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n4dvq9b6o"/><path class="n_2kbbb6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-ice-cream" {...props}></Icon>
