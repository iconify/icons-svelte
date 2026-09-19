<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lelhfpbde.css';
import '../../css/a/a4jsaxbri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lelhfpbde"/><path class="a4jsaxbri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:file-download-solid" {...props}></Icon>
