<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gl5abcb0s.css';
import '../../css/k/k3ds82w0c.css';
import '../../css/e/ebf9xob5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gl5abcb0s"/><path class="k3ds82w0c"/><path class="ebf9xob5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:capacitor-runtime-light" {...props}></Icon>
