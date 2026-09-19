<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wye1xtbgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="wye1xtbgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:boxing-glove-outline" {...props}></Icon>
