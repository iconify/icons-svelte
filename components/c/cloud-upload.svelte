<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/naq-blbtv.css';
import '../../css/l/l-0qc5b4i.css';
import '../../css/s/spe1s4bal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="naq-blbtv wm-k"/><path class="l-0qc5b4i wm-k"/><path class="spe1s4bal wm-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:cloud-upload" {...props}></Icon>
