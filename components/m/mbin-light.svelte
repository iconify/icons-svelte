<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhu35gblw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yhu35gblw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mbin-light" {...props}></Icon>
