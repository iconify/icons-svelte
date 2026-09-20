<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzgwzi7wr.css';
import '../../css/s/s7ybahwbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gzgwzi7wr"/><path class="s7ybahwbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:castopod" {...props}></Icon>
