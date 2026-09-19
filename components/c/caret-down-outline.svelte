<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvx0x29yb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gvx0x29yb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:caret-down-outline" {...props}></Icon>
