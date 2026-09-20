<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgv4qp2mj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kgv4qp2mj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-document-box-tick-outline" {...props}></Icon>
