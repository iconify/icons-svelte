<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hh9fonbif.css';
import '../../css/i/iqb1nzp3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hh9fonbif"/><path class="iqb1nzp3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mautic" {...props}></Icon>
