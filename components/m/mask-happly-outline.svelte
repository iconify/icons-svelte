<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ui57otb5r.css';
import '../../css/d/dpovio02y.css';
import '../../css/u/uaipmab5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ui57otb5r"/><path clip-rule="evenodd" class="dpovio02y"/><path class="uaipmab5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:mask-happly-outline" {...props}></Icon>
