<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mep25ehts.css';
import '../../css/s/s-xxlii2p.css';
import '../../css/s/s__9l0bok.css';
import '../../css/l/l01btobsp.css';
import '../../css/q/qy525jbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="mep25ehts"/><path class="s-xxlii2p"/><path class="s__9l0bok"/><path class="l01btobsp"/><path class="qy525jbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:flag-sao-tome-and-principe" {...props}></Icon>
