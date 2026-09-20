<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljmd1i_bj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ljmd1i_bj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:phylum" {...props}></Icon>
