<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l954m5b7x.css';
import '../../css/l/lvqwy803y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l954m5b7x"/><path class="lvqwy803y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:inspircd" {...props}></Icon>
