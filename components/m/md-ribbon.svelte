<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzj803jut.css';
import '../../css/s/s4_r7ab8r.css';
import '../../css/n/nk949cczd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tzj803jut"/><path class="s4_r7ab8r"/><path class="nk949cczd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-ribbon" {...props}></Icon>
