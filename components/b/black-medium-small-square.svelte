<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bh6n15bwy.css';
import '../../css/u/umdrjybhb.css';
import '../../css/b/bw_zhbbpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="bh6n15bwy"/><path class="umdrjybhb"/><path class="bw_zhbbpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:black-medium-small-square" {...props}></Icon>
