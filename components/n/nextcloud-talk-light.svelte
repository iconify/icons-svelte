<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nkekv2bib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nkekv2bib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextcloud-talk-light" {...props}></Icon>
