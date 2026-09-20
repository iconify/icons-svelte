<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjc1npbxs.css';
import '../../css/s/saj3nzkks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qjc1npbxs"/><path class="saj3nzkks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:frappe-builder" {...props}></Icon>
