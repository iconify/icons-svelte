<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xs1kckuxk.css';
import '../../css/y/ytnuvpdkn.css';
import '../../css/p/p4itqc0gf.css';
import '../../css/y/yav708big.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xs1kckuxk"/><path class="ytnuvpdkn"/><path class="p4itqc0gf"/><path class="yav708big"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-onenote-dark" {...props}></Icon>
