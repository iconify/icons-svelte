<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bpk81tlfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bpk81tlfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:american-eagle-dark" {...props}></Icon>
