<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0k0o1c2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="k0k0o1c2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:owm-301" {...props}></Icon>
