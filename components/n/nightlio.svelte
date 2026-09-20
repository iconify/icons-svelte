<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tw5h94i8m.css';
import '../../css/i/ingurx9qd.css';
import '../../css/u/u2ff1xk4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tw5h94i8m"/><path class="ingurx9qd"/><path class="u2ff1xk4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nightlio" {...props}></Icon>
