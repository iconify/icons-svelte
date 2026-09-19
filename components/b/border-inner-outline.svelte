<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxc2vnb9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="dxc2vnb9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:border-inner-outline" {...props}></Icon>
