<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzsbmhebc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pzsbmhebc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:city-14-filled" {...props}></Icon>
