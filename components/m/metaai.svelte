<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fl2p1fbmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fl2p1fbmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:metaai" {...props}></Icon>
