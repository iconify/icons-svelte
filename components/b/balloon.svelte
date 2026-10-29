<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhwwc2blb.css';
import '../../css/b/bef-jeb5r.css';
import '../../css/n/nz-mu3bbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fhwwc2blb wm-a"/><path class="bef-jeb5r wm-k"/><path class="nz-mu3bbv wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:balloon" {...props}></Icon>
