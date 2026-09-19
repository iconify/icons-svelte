<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dn7g7lbmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="dn7g7lbmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:internal-investigation" {...props}></Icon>
