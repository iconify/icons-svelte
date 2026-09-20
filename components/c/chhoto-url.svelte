<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kftxfzu5d.css';
import '../../css/d/dwh6i6b0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kftxfzu5d"/><path class="dwh6i6b0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:chhoto-url" {...props}></Icon>
