<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v73rypy0t.css';
import '../../css/d/dp85ht2pz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v73rypy0t"/><path class="dp85ht2pz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:qr-code-solid" {...props}></Icon>
