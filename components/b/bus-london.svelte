<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m515emb1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":472};
const content = `<path class="m515emb1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:bus-london" {...props}></Icon>
