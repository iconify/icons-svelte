<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phg1s7mys.css';
import '../../css/a/a35dc2b9v.css';
import '../../css/b/b681yhxlk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="phg1s7mys"/><path class="a35dc2b9v"/><path class="b681yhxlk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ente-locker-dark" {...props}></Icon>
