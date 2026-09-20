<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qc9f10m7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qc9f10m7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-document-box-minus-outline" {...props}></Icon>
