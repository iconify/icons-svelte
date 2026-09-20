<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lff5ccbxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lff5ccbxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:buhl" {...props}></Icon>
