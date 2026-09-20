<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kk-n8nb7r.css';
import '../../css/x/xizbhjbsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kk-n8nb7r"/><path class="xizbhjbsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:linkedin" {...props}></Icon>
