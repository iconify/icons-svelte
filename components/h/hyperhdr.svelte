<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbvk0jbkh.css';
import '../../css/s/sxrldrbfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sbvk0jbkh"/><path class="sxrldrbfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hyperhdr" {...props}></Icon>
