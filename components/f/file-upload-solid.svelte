<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbajkz4iu.css';
import '../../css/a/a4jsaxbri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qbajkz4iu"/><path class="a4jsaxbri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:file-upload-solid" {...props}></Icon>
