<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ara2u6bia.css';
import '../../css/g/g1ssb8box.css';
import '../../css/p/ps_nwu9ub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ara2u6bia"/><path class="g1ssb8box"/><path class="ps_nwu9ub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-podium" {...props}></Icon>
