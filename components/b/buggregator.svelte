<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c822n_byc.css';
import '../../css/j/jtxyyikiw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c822n_byc"/><path class="jtxyyikiw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:buggregator" {...props}></Icon>
