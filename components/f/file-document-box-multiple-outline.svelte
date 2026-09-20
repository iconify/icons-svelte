<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftl45_bmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ftl45_bmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-document-box-multiple-outline" {...props}></Icon>
