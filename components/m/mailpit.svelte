<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kljix3b2j.css';
import '../../css/g/gb6l_zk0s.css';
import '../../css/b/bbjq83b2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kljix3b2j"/><path class="gb6l_zk0s"/><path class="bbjq83b2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mailpit" {...props}></Icon>
