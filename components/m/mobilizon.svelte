<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b17oeotjk.css';
import '../../css/a/ad5qjploe.css';
import '../../css/l/lvcq9zb7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b17oeotjk"/><path class="ad5qjploe"/><path class="lvcq9zb7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mobilizon" {...props}></Icon>
