<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdw1bnmki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kdw1bnmki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-document-add-outline" {...props}></Icon>
