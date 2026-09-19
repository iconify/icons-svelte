<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7kqt_bhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="n7kqt_bhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:gift-outline" {...props}></Icon>
