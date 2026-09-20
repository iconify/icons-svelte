<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwsftlbby.css';
import '../../css/n/n-9-1s2vc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iwsftlbby"/><path class="n-9-1s2vc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:gosuki" {...props}></Icon>
