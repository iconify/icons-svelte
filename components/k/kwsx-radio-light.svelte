<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idfkpkbuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="idfkpkbuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kwsx-radio-light" {...props}></Icon>
