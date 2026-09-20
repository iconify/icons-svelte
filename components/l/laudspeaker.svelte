<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ko_s50v2q.css';
import '../../css/k/k0au53bzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ko_s50v2q"/><path class="k0au53bzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:laudspeaker" {...props}></Icon>
