<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ym02nvber.css';
import '../../css/u/unrc__8ri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ym02nvber"/><path clip-rule="evenodd" class="unrc__8ri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:playing-card-filled" {...props}></Icon>
