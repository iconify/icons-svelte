<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gljxhwefi.css';
import '../../css/l/lus1dsb7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gljxhwefi"/><path clip-rule="evenodd" class="lus1dsb7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:audio-document-solid" {...props}></Icon>
