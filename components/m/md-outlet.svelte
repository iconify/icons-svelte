<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwh-wgq9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xwh-wgq9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-outlet" {...props}></Icon>
