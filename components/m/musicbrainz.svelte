<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q25dr_b5z.css';
import '../../css/x/xoum1hbfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q25dr_b5z"/><path class="xoum1hbfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:musicbrainz" {...props}></Icon>
