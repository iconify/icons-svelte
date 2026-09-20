<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rok_s9ahy.css';
import '../../css/b/b4_i_1h2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rok_s9ahy"/><path class="b4_i_1h2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:espconnect-light" {...props}></Icon>
