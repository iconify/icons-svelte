<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v12d60_ju.css';
import '../../css/e/e29tvgbxj.css';
import '../../css/q/qdaqy6blz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v12d60_ju"/><path class="e29tvgbxj"/><path class="qdaqy6blz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:coolify" {...props}></Icon>
