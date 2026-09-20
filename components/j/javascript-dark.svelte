<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ot58emb2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ot58emb2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:javascript-dark" {...props}></Icon>
