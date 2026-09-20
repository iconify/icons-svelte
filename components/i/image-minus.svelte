<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kn9frpc1e.css';
import '../../css/o/ocxedjb1h.css';
import '../../css/i/i6107pbis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kn9frpc1e"/><path class="ocxedjb1h"/><path class="i6107pbis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:image-minus" {...props}></Icon>
