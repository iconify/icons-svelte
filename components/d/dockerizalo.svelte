<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgkqhtgri.css';
import '../../css/b/b7__w3xsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lgkqhtgri"/><path class="b7__w3xsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dockerizalo" {...props}></Icon>
