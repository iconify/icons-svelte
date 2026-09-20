<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cn_3n2bac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cn_3n2bac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hitkeep" {...props}></Icon>
