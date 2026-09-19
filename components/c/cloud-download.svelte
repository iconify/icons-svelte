<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqf5vsmca.css';
import '../../css/d/ddaib_rgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oqf5vsmca"/><path class="ddaib_rgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:cloud-download" {...props}></Icon>
