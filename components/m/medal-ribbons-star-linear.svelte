<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/v/vto_qpspa.css';
import '../../css/i/i6nrt8nnu.css';
import '../../css/p/p8kjf3qdz.css';
import '../../css/t/tvuqtkb4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="vto_qpspa"/><path class="i6nrt8nnu"/><path class="p8kjf3qdz"/><path class="tvuqtkb4q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:medal-ribbons-star-linear" {...props}></Icon>
