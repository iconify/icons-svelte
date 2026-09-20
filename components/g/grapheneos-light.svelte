<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1g1ml97w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u1g1ml97w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:grapheneos-light" {...props}></Icon>
