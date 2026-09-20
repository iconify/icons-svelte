<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2p29w2gw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f2p29w2gw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:qdirstat-dark" {...props}></Icon>
