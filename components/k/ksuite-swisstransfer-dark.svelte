<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/legs_-oed.css';
import '../../css/n/ny5b9ebqn.css';
import '../../css/n/n7g6991ym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="legs_-oed"/><path class="ny5b9ebqn"/><path class="n7g6991ym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ksuite-swisstransfer-dark" {...props}></Icon>
