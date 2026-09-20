<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/seopr-2dr.css';
import '../../css/i/iwarbo7oi.css';
import '../../css/p/ptikcmbbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="seopr-2dr"/><path class="iwarbo7oi"/><path class="ptikcmbbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:file-pdf-filled" {...props}></Icon>
