<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgwnx6eoh.css';
import '../../css/a/adak2ebid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pgwnx6eoh"/><path class="adak2ebid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:budgetbee" {...props}></Icon>
