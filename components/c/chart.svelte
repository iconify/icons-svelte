<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lq3qa1d7q.css';
import '../../css/i/itgv6gmfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lq3qa1d7q"/><path class="itgv6gmfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:chart" {...props}></Icon>
