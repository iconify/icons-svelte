<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9-ohxbke.css';
import '../../css/e/ehyq6ihjz.css';
import '../../css/q/qzrhlkbto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="x9-ohxbke"/><circle class="ehyq6ihjz"/><path class="qzrhlkbto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:cart" {...props}></Icon>
