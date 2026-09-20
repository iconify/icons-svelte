<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pq4y6eb-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pq4y6eb-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-document-box-tick" {...props}></Icon>
