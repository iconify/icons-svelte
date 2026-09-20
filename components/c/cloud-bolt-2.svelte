<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ii82hnrhg.css';
import '../../css/e/eu4o_3evy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":25};
const content = `<path class="ii82hnrhg"/><path clip-rule="evenodd" class="eu4o_3evy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:cloud-bolt-2" {...props}></Icon>
