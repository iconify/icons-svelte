<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fprq_0fsn.css';
import '../../css/p/p__zjibpv.css';
import '../../css/z/zsuyb4b9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fprq_0fsn"/><path class="p__zjibpv"/><path class="zsuyb4b9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rosterhash" {...props}></Icon>
