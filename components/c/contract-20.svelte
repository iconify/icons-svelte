<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-g74icta.css';
import '../../css/o/og5hr9b2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d-g74icta"/><path class="og5hr9b2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:contract-20" {...props}></Icon>
