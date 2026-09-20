<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijb908brc.css';
import '../../css/t/tucrirb7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="ijb908brc"/><path class="tucrirb7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:newshosting" {...props}></Icon>
